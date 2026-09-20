<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtr5x3_vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtr5x3_vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:interaction-double-tap" {...props}></Icon>
