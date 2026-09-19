<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw38rabuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="yw38rabuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:crop-1-outline" {...props}></Icon>
