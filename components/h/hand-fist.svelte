<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnjp8ib7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xnjp8ib7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:hand-fist" {...props}></Icon>
