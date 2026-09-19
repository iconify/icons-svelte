<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/nde60ab7m.css';
import '../../css/e/ez_zj8b4g.css';
import '../../css/a/arg04jbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="nde60ab7m"/><path class="ez_zj8b4g"/><path class="arg04jbjn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:facial-mask" {...props}></Icon>
