<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/m3mjhjsib.css';
import '../../css/u/uw7kh3tvy.css';
import '../../css/z/z70us2r6z.css';
import '../../css/t/td_xgwz2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="m3mjhjsib"/><path class="uw7kh3tvy"/><path class="z70us2r6z"/><path class="td_xgwz2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:flowchart-02" {...props}></Icon>
