<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbt0vhszc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="hbt0vhszc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:die-5-bold" {...props}></Icon>
