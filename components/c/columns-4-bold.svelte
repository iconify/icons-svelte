<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i4c_pmb7m.css';
import '../../css/y/y9rzt59_w.css';
import '../../css/u/uf_5n0bwx.css';
import '../../css/k/klv35m69y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i4c_pmb7m"/><path class="y9rzt59_w"/><path class="uf_5n0bwx"/><path class="klv35m69y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-4-bold" {...props}></Icon>
