<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygi4r2b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygi4r2b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-area-round" {...props}></Icon>
