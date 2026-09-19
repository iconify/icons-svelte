<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bo1_r_bkn.css';
import '../../css/k/k_95onbhk.css';
import '../../css/x/xy7bfo4gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="bo1_r_bkn"/><path class="k_95onbhk"/><rect class="xy7bfo4gq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:newspaper" {...props}></Icon>
