<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e--nlzj6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e--nlzj6l wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:drag-handle-sketch" {...props}></Icon>
