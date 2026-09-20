<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik8url33b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik8url33b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-y-circle" {...props}></Icon>
