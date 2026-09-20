<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc_22wbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc_22wbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-3-line" {...props}></Icon>
