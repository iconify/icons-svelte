<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0kbp0bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="f0kbp0bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grid-remove" {...props}></Icon>
