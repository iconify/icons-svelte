<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rezs91bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rezs91bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:door-open" {...props}></Icon>
