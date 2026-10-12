<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wier_vbdb.css';
import '../../css/t/tv-on1bdd.css';
import '../../css/w/w1f5z-fwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wier_vbdb"/><path class="tv-on1bdd"/><path class="w1f5z-fwf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-horizontal-space-between-duotone" {...props}></Icon>
