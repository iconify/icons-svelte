<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frk4m0bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="frk4m0bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:phone-remove" {...props}></Icon>
