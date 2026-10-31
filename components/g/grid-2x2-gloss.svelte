<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by0mu6bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by0mu6bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:grid-2x2-gloss" {...props}></Icon>
