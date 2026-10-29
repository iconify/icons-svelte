<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j0ggkhb1g.css';
import '../../css/d/d5_gd2mux.css';
import '../../css/y/yo87urbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j0ggkhb1g"/><path class="d5_gd2mux wm-a"/><path class="yo87urbrl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:martini-duo" {...props}></Icon>
