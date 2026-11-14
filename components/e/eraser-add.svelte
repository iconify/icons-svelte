<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auz8qgbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auz8qgbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:eraser-add" {...props}></Icon>
