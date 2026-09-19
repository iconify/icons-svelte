<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/z-3dhhb_i.css';
import '../../css/h/hmvldzbaf.css';
import '../../css/t/tewkg6wrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="z-3dhhb_i"/><circle class="hmvldzbaf"/><path class="tewkg6wrh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:robot-two" {...props}></Icon>
