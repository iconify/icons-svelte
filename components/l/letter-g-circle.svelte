<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_30q3cbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_30q3cbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-g-circle" {...props}></Icon>
