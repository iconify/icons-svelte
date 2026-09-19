<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kb9zbkb1z.css';
import '../../css/h/hy6yzlbvz.css';
import '../../css/z/zsls1eb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="kb9zbkb1z"/><path class="hy6yzlbvz"/><path class="zsls1eb-j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:jewelry" {...props}></Icon>
