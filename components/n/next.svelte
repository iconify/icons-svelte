<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptdi0xbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptdi0xbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:next" {...props}></Icon>
