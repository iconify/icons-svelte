<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i27jy566b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="i27jy566b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:activity-1" {...props}></Icon>
