<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pscmmybmb.css';
import '../../css/k/kfr1grbjb.css';
import '../../css/y/y4ucstbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pscmmybmb"/><path class="kfr1grbjb"/><circle class="y4ucstbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:instagram-original" {...props}></Icon>
