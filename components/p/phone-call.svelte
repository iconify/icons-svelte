<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr3ccxb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr3ccxb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:phone-call" {...props}></Icon>
