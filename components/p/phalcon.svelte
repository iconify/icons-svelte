<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkpplc3oo.css';
import '../../css/m/mbgl0xb_o.css';
import '../../css/e/eg0azubuo.css';
import '../../css/k/kz_b-it7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pkpplc3oo"/><path class="mbgl0xb_o"/><path class="eg0azubuo"/><path class="kz_b-it7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:phalcon" {...props}></Icon>
