<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-lsfljsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="d-lsfljsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hourglass-2-bold" {...props}></Icon>
