<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfjone-3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="gfjone-3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:eraser" {...props}></Icon>
