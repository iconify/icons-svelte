<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njixr5bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="njixr5bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hash-bold" {...props}></Icon>
