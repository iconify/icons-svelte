<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k1_pjbc3p.css';
import '../../css/v/vwgo760mv.css';
import '../../css/j/jf6is2dzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="k1_pjbc3p"/><path class="vwgo760mv"/><circle class="jf6is2dzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:duck" {...props}></Icon>
