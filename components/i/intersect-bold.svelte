<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hafyv4dci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hafyv4dci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:intersect-bold" {...props}></Icon>
