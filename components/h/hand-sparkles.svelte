<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa8fm1bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pa8fm1bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hand-sparkles" {...props}></Icon>
