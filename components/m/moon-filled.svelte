<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwg8mfbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwg8mfbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:moon-filled" {...props}></Icon>
