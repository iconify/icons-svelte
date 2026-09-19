<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmdeh4btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="lmdeh4btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cloud-1" {...props}></Icon>
