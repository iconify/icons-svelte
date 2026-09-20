<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r88s88b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r88s88b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:battery-charging" {...props}></Icon>
