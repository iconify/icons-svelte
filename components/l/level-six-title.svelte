<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/l_b2deb8g.css';
import '../../css/i/i81rab26g.css';
import '../../css/i/i3l2mxbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="l_b2deb8g"/><path class="i81rab26g"/><path class="i3l2mxbql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:level-six-title" {...props}></Icon>
