<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzit4obey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yzit4obey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-line-end-outline" {...props}></Icon>
