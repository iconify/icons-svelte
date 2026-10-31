<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc1jwlbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yc1jwlbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-help-fill-round" {...props}></Icon>
