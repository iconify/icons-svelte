<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3r8h6w8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3r8h6w8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:elevator-passenger-off" {...props}></Icon>
