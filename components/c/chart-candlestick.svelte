<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk8u-1b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk8u-1b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-candlestick" {...props}></Icon>
