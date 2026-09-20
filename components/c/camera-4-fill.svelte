<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nabc9hbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nabc9hbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:camera-4-fill" {...props}></Icon>
