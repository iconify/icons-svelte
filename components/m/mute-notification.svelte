<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3doxobej.css';
import '../../css/c/czogqxb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e3doxobej"/><path class="czogqxb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:mute-notification" {...props}></Icon>
