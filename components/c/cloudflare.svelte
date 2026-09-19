<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwpk_5b-d.css';
import '../../css/g/guwa6_8ak.css';
import '../../css/v/v_sn19bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zwpk_5b-d"/><path class="guwa6_8ak"/><path class="v_sn19bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:cloudflare" {...props}></Icon>
