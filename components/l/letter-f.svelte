<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh7gp0bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh7gp0bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-f" {...props}></Icon>
