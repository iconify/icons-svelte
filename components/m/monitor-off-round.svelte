<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk3qy-tdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk3qy-tdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-off-round" {...props}></Icon>
