<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5xyj_yyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5xyj_yyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:3d-cube-sphere-off" {...props}></Icon>
