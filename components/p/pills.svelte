<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es7ggpb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="es7ggpb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pills" {...props}></Icon>
