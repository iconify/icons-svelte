<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcq9aufca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcq9aufca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:door-closed-sharp" {...props}></Icon>
