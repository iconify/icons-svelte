<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww4ub9yah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ww4ub9yah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:notification-2-fill" {...props}></Icon>
