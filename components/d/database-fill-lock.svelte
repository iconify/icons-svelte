<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k1ay2cgzn.css';
import '../../css/t/tq0msdb1x.css';
import '../../css/m/mx6q5eb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="k1ay2cgzn"/><path class="tq0msdb1x"/><path class="mx6q5eb8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:database-fill-lock" {...props}></Icon>
