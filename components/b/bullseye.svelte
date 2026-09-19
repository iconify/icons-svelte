<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mj4w1gb3h.css';
import '../../css/a/a7zzmybnf.css';
import '../../css/w/wt_x01hno.css';
import '../../css/s/smag3rbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="mj4w1gb3h"/><path class="a7zzmybnf"/><path class="wt_x01hno"/><path class="smag3rbcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bullseye" {...props}></Icon>
