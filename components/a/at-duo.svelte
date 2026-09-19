<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afl-tve-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="afl-tve-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:at-duo" {...props}></Icon>
