<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/k0n-ptb0u.css';
import '../../css/c/cp5t-n2_r.css';
import '../../css/y/ysqi2pc_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k0n-ptb0u"/><path class="cp5t-n2_r"/><path class="ysqi2pc_u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:doc-search" {...props}></Icon>
