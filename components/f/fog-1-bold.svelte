<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr4ur_7jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="mr4ur_7jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fog-1-bold" {...props}></Icon>
