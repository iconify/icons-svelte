<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cgp52u_px.css';
import '../../css/f/foyapdb-p.css';
import '../../css/k/kvkb1-boj.css';
import '../../css/k/kigi6xf5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cgp52u_px"/><path clip-rule="evenodd" class="foyapdb-p"/><path class="kvkb1-boj"/><path class="kigi6xf5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flashlight-on-duotone" {...props}></Icon>
