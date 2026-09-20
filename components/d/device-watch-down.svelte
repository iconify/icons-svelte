<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikp_rhbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikp_rhbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-down" {...props}></Icon>
