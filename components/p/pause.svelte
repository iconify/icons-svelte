<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll5m0r9ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll5m0r9ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pause" {...props}></Icon>
