<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8fhi_b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8fhi_b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:flip-horizontal-2" {...props}></Icon>
