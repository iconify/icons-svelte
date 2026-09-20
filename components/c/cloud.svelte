<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/u/u7n78m30y.css';
import '../../css/n/ndvxg3usm.css';
import '../../css/r/rl5sxph5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="u7n78m30y"/><path class="ndvxg3usm"/><path class="rl5sxph5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:cloud" {...props}></Icon>
