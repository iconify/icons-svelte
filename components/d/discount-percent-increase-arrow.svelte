<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1cp0nbej.css';
import '../../css/e/em0p01pxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1cp0nbej"/><path class="em0p01pxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:discount-percent-increase-arrow" {...props}></Icon>
