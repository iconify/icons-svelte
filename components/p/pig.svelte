<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hxgpq414k.css';
import '../../css/u/uf3oh5bzw.css';
import '../../css/p/p3o7oy_bq.css';
import '../../css/c/c70km2biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hxgpq414k"/><path clip-rule="evenodd" class="uf3oh5bzw"/><path class="p3o7oy_bq"/><path clip-rule="evenodd" class="c70km2biw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:pig" {...props}></Icon>
