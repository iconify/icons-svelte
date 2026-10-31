<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccoiadrin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccoiadrin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:forward-gloss" {...props}></Icon>
