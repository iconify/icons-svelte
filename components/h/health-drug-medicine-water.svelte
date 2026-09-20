<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2lo1actl.css';
import '../../css/u/utw1vrodv.css';
import '../../css/y/y016e8ire.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d2lo1actl"/><path class="utw1vrodv"/><path class="y016e8ire"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-drug-medicine-water" {...props}></Icon>
