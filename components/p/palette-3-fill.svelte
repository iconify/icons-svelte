<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4shc1bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4shc1bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:palette-3-fill" {...props}></Icon>
