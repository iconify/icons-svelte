<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihb73o3yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihb73o3yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:palette-line" {...props}></Icon>
