<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xydpt3bmg.css';
import '../../css/m/mmtmrcb2y.css';
import '../../css/d/d-rqrld-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xydpt3bmg"/><path class="mmtmrcb2y"/><path class="d-rqrld-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hotel-20" {...props}></Icon>
