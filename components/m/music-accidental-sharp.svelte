<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe7m4oy-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe7m4oy-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-accidental-sharp" {...props}></Icon>
