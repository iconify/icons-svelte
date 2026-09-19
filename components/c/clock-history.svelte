<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u6yb07oyv.css';
import '../../css/x/xok_n9bbo.css';
import '../../css/n/nc18fzb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="u6yb07oyv"/><path class="xok_n9bbo"/><path class="nc18fzb9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:clock-history" {...props}></Icon>
