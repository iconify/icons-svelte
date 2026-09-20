<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc6xhac8s.css';
import '../../css/p/p-3va582c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc6xhac8s"/><path class="p-3va582c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:messages-bubble-image" {...props}></Icon>
