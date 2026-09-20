<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l-5n86b-i.css';
import '../../css/l/li_x_qb7t.css';
import '../../css/q/q4fuubn3g.css';
import '../../css/f/fpmrqqzwz.css';
import '../../css/y/yjogm03ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l-5n86b-i"/><path class="li_x_qb7t"/><path class="q4fuubn3g"/><path clip-rule="evenodd" class="fpmrqqzwz"/><path class="yjogm03ma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cassette-2-bold" {...props}></Icon>
