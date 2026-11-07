<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vq8p2ub8p.css';
import '../../css/k/koojm6b6e.css';
import '../../css/g/gg51fnb0j.css';
import '../../css/r/rultmacqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vq8p2ub8p"/><path class="koojm6b6e"/><path class="gg51fnb0j"/><path class="rultmacqq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:blocks-broken" {...props}></Icon>
