<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru8guwb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru8guwb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:id-card" {...props}></Icon>
