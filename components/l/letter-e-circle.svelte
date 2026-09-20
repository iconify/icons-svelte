<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxzi_ye4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxzi_ye4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-e-circle" {...props}></Icon>
