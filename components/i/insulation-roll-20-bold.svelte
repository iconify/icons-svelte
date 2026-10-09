<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2do86btb.css';
import '../../css/w/wh481vbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i2do86btb"/><path class="wh481vbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:insulation-roll-20-bold" {...props}></Icon>
