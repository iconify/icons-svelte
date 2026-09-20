<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqvc2kbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqvc2kbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-high" {...props}></Icon>
