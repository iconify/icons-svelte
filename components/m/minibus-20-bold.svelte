<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcs7_0bhg.css';
import '../../css/x/xreezc2ol.css';
import '../../css/u/utbp3ny_p.css';
import '../../css/x/x3ecq6b_k.css';
import '../../css/u/uoea4uo8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bcs7_0bhg"/><path class="xreezc2ol"/><path class="utbp3ny_p"/><path class="x3ecq6b_k"/><path class="uoea4uo8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:minibus-20-bold" {...props}></Icon>
