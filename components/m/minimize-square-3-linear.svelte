<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cb03pibjf.css';
import '../../css/v/vv3m6lbyb.css';
import '../../css/y/yqghi_b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cb03pibjf"/><path class="vv3m6lbyb"/><path class="yqghi_b_r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimize-square-3-linear" {...props}></Icon>
