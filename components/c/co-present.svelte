<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wena4ilcp.css';
import '../../css/l/lmegi90tj.css';
import '../../css/k/kwfnbbc6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="wena4ilcp"/><path class="lmegi90tj"/><path class="kwfnbbc6d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:co-present" {...props}></Icon>
