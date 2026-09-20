<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9l3hbf0t.css';
import '../../css/y/y0j0mcbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u9l3hbf0t"/><path class="y0j0mcbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-harvester" {...props}></Icon>
