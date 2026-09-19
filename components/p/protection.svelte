<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kmql86b4y.css';
import '../../css/x/xx16e09lg.css';
import '../../css/u/urcvvqb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="kmql86b4y"/><path class="xx16e09lg"/><path class="urcvvqb_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:protection" {...props}></Icon>
