<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc6xhac8s.css';
import '../../css/b/bgwitbc3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc6xhac8s"/><path class="bgwitbc3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:messages-bubble-menu" {...props}></Icon>
