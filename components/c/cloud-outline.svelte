<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vexnywh-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="vexnywh-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cloud-outline" {...props}></Icon>
