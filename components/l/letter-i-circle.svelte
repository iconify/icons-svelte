<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmacnk1qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmacnk1qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-i-circle" {...props}></Icon>
