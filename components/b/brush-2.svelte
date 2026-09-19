<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9mhcml7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l9mhcml7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:brush-2" {...props}></Icon>
