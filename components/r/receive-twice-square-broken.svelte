<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/slo5fwl1o.css';
import '../../css/w/ws1lyv0so.css';
import '../../css/u/ufwicgbql.css';
import '../../css/s/si_mtzbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="slo5fwl1o"/><path class="ws1lyv0so"/><path class="ufwicgbql"/><path class="si_mtzbvj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:receive-twice-square-broken" {...props}></Icon>
