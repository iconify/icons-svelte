<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwjaptb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwjaptb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fan-auto" {...props}></Icon>
