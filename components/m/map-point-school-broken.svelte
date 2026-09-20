<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d0tglh60a.css';
import '../../css/t/toskudjye.css';
import '../../css/p/p9u0eeb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d0tglh60a"/><path class="toskudjye"/><path class="p9u0eeb3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-school-broken" {...props}></Icon>
