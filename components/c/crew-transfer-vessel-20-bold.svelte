<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtt8v1bcn.css';
import '../../css/h/h2cw1srdy.css';
import '../../css/o/o_4o-hjdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rtt8v1bcn"/><path class="h2cw1srdy"/><path class="o_4o-hjdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crew-transfer-vessel-20-bold" {...props}></Icon>
