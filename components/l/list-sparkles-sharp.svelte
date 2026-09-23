<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/j/j-y4i4biy.css';
import '../../css/y/yqe6_cdnh.css';
import '../../css/m/mf_m6jlzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j-y4i4biy"/><path class="yqe6_cdnh"/><path class="mf_m6jlzc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-sparkles-sharp" {...props}></Icon>
