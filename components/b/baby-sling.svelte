<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/ru8s1dvas.css';
import '../../css/l/lemb12btl.css';
import '../../css/p/plqe-22_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="ru8s1dvas"/><path class="lemb12btl"/><path class="plqe-22_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:baby-sling" {...props}></Icon>
