<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbko2ebwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbko2ebwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:oracle" {...props}></Icon>
