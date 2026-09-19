<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2do5-bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="l2do5-bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:g" {...props}></Icon>
