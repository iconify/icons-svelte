<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhqi1ub4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vhqi1ub4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:line" {...props}></Icon>
