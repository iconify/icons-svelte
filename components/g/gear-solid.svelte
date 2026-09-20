<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmb45tbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmb45tbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:gear-solid" {...props}></Icon>
