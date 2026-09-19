<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7wfuwb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="f7wfuwb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-lines" {...props}></Icon>
