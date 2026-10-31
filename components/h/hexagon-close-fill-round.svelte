<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzv3ysyde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzv3ysyde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-close-fill-round" {...props}></Icon>
