<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytt8pvboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytt8pvboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-scatter-3d" {...props}></Icon>
