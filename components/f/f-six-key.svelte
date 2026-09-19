<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/n03w5kbkh.css';
import '../../css/v/v0sklzfxn.css';
import '../../css/d/dhap0cc7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="n03w5kbkh"/><path class="v0sklzfxn"/><path class="dhap0cc7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:f-six-key" {...props}></Icon>
