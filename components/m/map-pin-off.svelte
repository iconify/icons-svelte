<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqn50zb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqn50zb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:map-pin-off" {...props}></Icon>
