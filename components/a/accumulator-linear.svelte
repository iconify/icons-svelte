<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yq5tzwbme.css';
import '../../css/s/slk4sp16n.css';
import '../../css/d/dicainbtc.css';
import '../../css/u/uibc2sgoa.css';
import '../../css/o/oid9cg9wl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yq5tzwbme"/><path class="slk4sp16n"/><path class="dicainbtc"/><path class="uibc2sgoa"/><path class="oid9cg9wl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:accumulator-linear" {...props}></Icon>
