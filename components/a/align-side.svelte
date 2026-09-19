<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xldwc8vhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xldwc8vhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:align-side" {...props}></Icon>
