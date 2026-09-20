<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhah0tblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="bhah0tblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:fullscreen" {...props}></Icon>
