<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/d/dix8kzfkx.css';
import '../../css/v/vur_a_bje.css';
import '../../css/n/ncgacjnek.css';
import '../../css/o/o4em-hsef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="dix8kzfkx wm-deco"/><path class="vur_a_bje wm-deco"/><path class="ncgacjnek wm-deco"/><path class="o4em-hsef"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bee-blueprint" {...props}></Icon>
