<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9vy1xbem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9vy1xbem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pencil-box-outline" {...props}></Icon>
