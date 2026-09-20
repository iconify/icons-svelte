<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9vy71bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9vy71bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dvd-fill" {...props}></Icon>
