<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sca024b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="sca024b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-holding-heart" {...props}></Icon>
