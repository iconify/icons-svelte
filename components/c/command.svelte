<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs07opbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rs07opbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:command" {...props}></Icon>
