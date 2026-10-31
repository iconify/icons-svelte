<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz4e8gbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz4e8gbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-off-fill-round" {...props}></Icon>
