<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv7tfu3sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv7tfu3sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:eraser-01" {...props}></Icon>
