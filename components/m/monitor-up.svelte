<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uuw1qkbsv.css';
import '../../css/g/gex1tzbfc.css';
import '../../css/o/o6x_rcbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="uuw1qkbsv"/><path class="gex1tzbfc"/><path class="o6x_rcbzj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-up" {...props}></Icon>
