<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psu4j2bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psu4j2bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:human-arms-up" {...props}></Icon>
