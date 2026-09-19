<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/b/bxg23zbzy.css';
import '../../css/h/h_u7y3bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><path class="bxg23zbzy"/><rect class="h_u7y3bpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lock-unlocked-stroke-12" {...props}></Icon>
