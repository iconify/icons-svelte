<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0phu2bbs.css';
import '../../css/m/m4l-9ybuj.css';
import '../../css/q/qlxamfbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><circle class="m4l-9ybuj"/><path class="qlxamfbej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-3-circle-bold" {...props}></Icon>
