<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iny_z7-rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="iny_z7-rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:gamepad-bold" {...props}></Icon>
