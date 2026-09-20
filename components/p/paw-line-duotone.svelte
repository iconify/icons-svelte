<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/of1pldrdd.css';
import '../../css/l/lwth1y9ze.css';
import '../../css/d/du6ayylxo.css';
import '../../css/w/wwlql7biu.css';
import '../../css/a/a_g57bd-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="of1pldrdd"/><path class="lwth1y9ze"/><path class="du6ayylxo"/><path class="wwlql7biu"/><path class="a_g57bd-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paw-line-duotone" {...props}></Icon>
