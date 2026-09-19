<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bkse_3btc.css';
import '../../css/m/mt2z4gbcg.css';
import '../../css/f/fb4sl08kb.css';
import '../../css/s/spenc4h9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bkse_3btc"/><path clip-rule="evenodd" class="mt2z4gbcg"/><path class="fb4sl08kb"/><path clip-rule="evenodd" class="spenc4h9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-line-end-outline" {...props}></Icon>
