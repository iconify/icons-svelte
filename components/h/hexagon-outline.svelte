<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xljq6k5dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xljq6k5dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hexagon-outline" {...props}></Icon>
