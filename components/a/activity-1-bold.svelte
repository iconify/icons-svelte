<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb9ucoekk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="gb9ucoekk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:activity-1-bold" {...props}></Icon>
