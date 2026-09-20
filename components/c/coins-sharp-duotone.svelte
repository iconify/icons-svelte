<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/j41a42nnh.css';
import '../../css/y/y5hju585n.css';
import '../../css/r/rkjqeacdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j41a42nnh"/><path clip-rule="evenodd" class="y5hju585n"/><path class="rkjqeacdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:coins-sharp-duotone" {...props}></Icon>
