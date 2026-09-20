<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9-dj30pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9-dj30pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:discord-solid" {...props}></Icon>
