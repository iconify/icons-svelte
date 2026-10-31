<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep8-spb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep8-spb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:refresh-gloss" {...props}></Icon>
