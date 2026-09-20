<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1jm6f-dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1jm6f-dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fan-speed-1" {...props}></Icon>
