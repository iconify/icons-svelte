<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r82adyb7b.css';
import '../../css/h/hj8ko8a3r.css';
import '../../css/t/tf1lulb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r82adyb7b"/><path class="hj8ko8a3r"/><path class="tf1lulb6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:drops-duotone" {...props}></Icon>
