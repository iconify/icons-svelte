<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/d/dlpf9rbdg.css';
import '../../css/q/qy-xuybra.css';
import '../../css/h/hk92wwirk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="dlpf9rbdg"/><path class="qy-xuybra"/><path class="hk92wwirk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bring-to-front" {...props}></Icon>
