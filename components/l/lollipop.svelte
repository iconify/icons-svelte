<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjp_koc1i.css';
import '../../css/l/l6yehs63f.css';
import '../../css/g/ghhg-0_2c.css';
import '../../css/u/uj_9lubin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sjp_koc1i"/><path class="l6yehs63f"/><circle class="ghhg-0_2c"/><path class="uj_9lubin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:lollipop" {...props}></Icon>
