<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5xt_g81n.css';
import '../../css/y/ysmbq7bxl.css';
import '../../css/d/d79oyzb2x.css';
import '../../css/d/d1ym2h3ya.css';
import '../../css/r/rd_oh8biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5xt_g81n"/><path class="ysmbq7bxl"/><circle class="d79oyzb2x"/><circle class="d1ym2h3ya"/><path class="rd_oh8biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:machine-learning" {...props}></Icon>
