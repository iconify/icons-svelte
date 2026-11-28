<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz29mwb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz29mwb_w primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-candlestick-duotone" {...props}></Icon>
