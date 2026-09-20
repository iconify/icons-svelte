<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k61-bn06g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k61-bn06g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:bitcoin" {...props}></Icon>
