<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp3n8fbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pp3n8fbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-holding-dollar" {...props}></Icon>
