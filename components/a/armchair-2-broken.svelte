<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vq0aepb-y.css';
import '../../css/q/q9yxfza0g.css';
import '../../css/y/y38gaub1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vq0aepb-y"/><path class="q9yxfza0g"/><path class="y38gaub1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:armchair-2-broken" {...props}></Icon>
