<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn6lqzhve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn6lqzhve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:led-strip" {...props}></Icon>
