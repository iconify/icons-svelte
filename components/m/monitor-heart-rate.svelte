<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xywstjb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xywstjb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:monitor-heart-rate" {...props}></Icon>
