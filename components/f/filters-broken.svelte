<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wr5xmnbwg.css';
import '../../css/b/bzm4__bgx.css';
import '../../css/u/u-x6mqgqh.css';
import '../../css/q/q9_xxzb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wr5xmnbwg"/><path class="bzm4__bgx"/><path class="u-x6mqgqh"/><path class="q9_xxzb_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filters-broken" {...props}></Icon>
