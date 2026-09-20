<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsb22-d5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsb22-d5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:more-horizontal-sharp" {...props}></Icon>
