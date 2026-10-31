<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfp_h_bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfp_h_bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-bar-horizontal-fill-round" {...props}></Icon>
