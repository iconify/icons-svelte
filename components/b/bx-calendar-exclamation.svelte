<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfc4wub2q.css';
import '../../css/a/az_hkit1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfc4wub2q"/><path class="az_hkit1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-calendar-exclamation" {...props}></Icon>
