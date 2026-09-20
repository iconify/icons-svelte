<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/w/wjltsrbuw.css';
import '../../css/q/qgjlc3dkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wjltsrbuw"/><path class="qgjlc3dkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:line-chart-square" {...props}></Icon>
