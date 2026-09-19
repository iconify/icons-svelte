<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/n-la1r_pz.css';
import '../../css/k/k7bf7us5u.css';
import '../../css/l/l7tubublb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="n-la1r_pz"/><path class="k7bf7us5u"/><path class="l7tubublb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:horizontal-resize" {...props}></Icon>
