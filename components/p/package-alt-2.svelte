<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/w/w7lfhmbwk.css';
import '../../css/p/pard6diuc.css';
import '../../css/k/kou1ambby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="w7lfhmbwk"/><path class="pard6diuc"/><path class="kou1ambby"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:package-alt-2" {...props}></Icon>
