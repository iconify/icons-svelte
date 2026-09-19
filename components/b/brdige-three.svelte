<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/y/ydeugkbob.css';
import '../../css/u/umtsztb2x.css';
import '../../css/f/f64a49b2p.css';
import '../../css/j/jr9v2-bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ydeugkbob"/><path class="umtsztb2x"/><path class="f64a49b2p"/><path class="jr9v2-bwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:brdige-three" {...props}></Icon>
