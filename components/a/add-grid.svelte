<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1bn7-8_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1bn7-8_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:add-grid" {...props}></Icon>
