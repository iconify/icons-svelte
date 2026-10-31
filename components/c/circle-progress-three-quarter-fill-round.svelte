<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4l8xj2ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4l8xj2ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-progress-three-quarter-fill-round" {...props}></Icon>
