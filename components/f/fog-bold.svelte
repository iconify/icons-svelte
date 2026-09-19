<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzebt0ozr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="lzebt0ozr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:fog-bold" {...props}></Icon>
