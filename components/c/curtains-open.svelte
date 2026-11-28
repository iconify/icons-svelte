<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ub4u4kwda.css';
import '../../css/u/u7s_38bqj.css';
import '../../css/o/ozqj7zbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ub4u4kwda"/><path class="u7s_38bqj"/><path class="ozqj7zbsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:curtains-open" {...props}></Icon>
