<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjc9fdfhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjc9fdfhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:luggage" {...props}></Icon>
