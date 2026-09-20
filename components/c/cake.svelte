<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8715gb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8715gb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:cake" {...props}></Icon>
