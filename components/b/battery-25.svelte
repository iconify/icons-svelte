<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akrx86noy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="akrx86noy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-25" {...props}></Icon>
