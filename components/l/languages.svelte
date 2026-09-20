<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xys4lib4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xys4lib4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:languages" {...props}></Icon>
