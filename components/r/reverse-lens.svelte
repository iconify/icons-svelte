<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/d/da_5j4bpz.css';
import '../../css/v/vm1b4_bnl.css';
import '../../css/o/o6ry9g4ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="da_5j4bpz"/><path class="vm1b4_bnl"/><path class="o6ry9g4ed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:reverse-lens" {...props}></Icon>
