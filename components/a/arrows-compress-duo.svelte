<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_-xccbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s_-xccbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrows-compress-duo" {...props}></Icon>
