<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k1ay2cgzn.css';
import '../../css/w/wuztmgkkn.css';
import '../../css/b/b46u4hbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="k1ay2cgzn"/><path class="wuztmgkkn"/><path class="b46u4hbqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:database-fill-x" {...props}></Icon>
