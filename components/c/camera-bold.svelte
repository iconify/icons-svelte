<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afilt3-px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="afilt3-px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:camera-bold" {...props}></Icon>
