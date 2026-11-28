<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhfyesugx.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uuw1qkbsv.css';
import '../../css/g/gex1tzbfc.css';
import '../../css/z/zuchoob5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary xhfyesugx"/><g class="dt0cm9dhy primary"><path class="uuw1qkbsv"/><path class="gex1tzbfc"/><path class="zuchoob5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monitor-down-duo" {...props}></Icon>
