<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouu7mgbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouu7mgbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:attachment" {...props}></Icon>
