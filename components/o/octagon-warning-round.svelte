<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdymc7ifa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdymc7ifa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:octagon-warning-round" {...props}></Icon>
