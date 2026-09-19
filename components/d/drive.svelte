<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/v9acwmm1g.css';
import '../../css/l/lant7tb4p.css';
import '../../css/e/ey0latwck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9acwmm1g"/><path class="lant7tb4p"/><path class="ey0latwck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:drive" {...props}></Icon>
