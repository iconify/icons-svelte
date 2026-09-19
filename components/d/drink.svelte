<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/q/qotkwl1bf.css';
import '../../css/o/omjh3bb_f.css';
import '../../css/c/cnw7n79ym.css';
import '../../css/q/q_9icnb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="qotkwl1bf"/><path class="omjh3bb_f"/><path class="cnw7n79ym"/><path class="q_9icnb5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:drink" {...props}></Icon>
