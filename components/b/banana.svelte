<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj0k1_ban.css';
import '../../css/u/uwnailbic.css';
import '../../css/a/ab7e5tb5k.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/w/w4vkojbmr.css';
import '../../css/j/j6_gv1bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="lj0k1_ban"><path class="uwnailbic"/><path class="ab7e5tb5k"/></g><g class="jn8qy4bru"><path class="w4vkojbmr"/><path class="j6_gv1bjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:banana" {...props}></Icon>
