<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erzf03bmv.css';
import '../../css/h/hll1-sbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="erzf03bmv"/><path class="hll1-sbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:miniflux" {...props}></Icon>
