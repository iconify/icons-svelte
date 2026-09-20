<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xn39h-g0p.css';
import '../../css/b/b8zhl9blw.css';
import '../../css/w/wewxyhbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xn39h-g0p"/><path clip-rule="evenodd" class="b8zhl9blw"/><path class="wewxyhbwh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:map" {...props}></Icon>
