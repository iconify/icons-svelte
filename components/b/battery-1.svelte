<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulaanbc5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulaanbc5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:battery-1" {...props}></Icon>
