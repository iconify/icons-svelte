<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/z01qkqb2l.css';
import '../../css/q/q37jtebrq.css';
import '../../css/n/n92m255cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path clip-rule="evenodd" class="z01qkqb2l"/><path class="q37jtebrq"/><path class="n92m255cp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:mask" {...props}></Icon>
