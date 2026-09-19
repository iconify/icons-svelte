<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x80n7zxwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x80n7zxwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:monitor" {...props}></Icon>
