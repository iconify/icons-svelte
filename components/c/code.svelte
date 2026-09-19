<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzef6e9ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="gzef6e9ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:code" {...props}></Icon>
