<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eeeecibaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="eeeecibaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:adr" {...props}></Icon>
