<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/t/tqw8k0f0r.css';
import '../../css/i/ir6hycbbm.css';
import '../../css/t/tbm68bcwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="tqw8k0f0r"/><path class="ir6hycbbm"/><circle class="tbm68bcwo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cd" {...props}></Icon>
