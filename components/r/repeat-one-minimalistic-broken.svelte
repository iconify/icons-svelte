<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e1y9aqblm.css';
import '../../css/i/i0bv9be2e.css';
import '../../css/p/pop59pb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e1y9aqblm"/><path class="i0bv9be2e"/><path class="pop59pb2d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:repeat-one-minimalistic-broken" {...props}></Icon>
