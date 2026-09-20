<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk4dx0bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk4dx0bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:lightbulb-off" {...props}></Icon>
