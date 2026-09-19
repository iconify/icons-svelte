<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4kagqb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="f4kagqb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:buildings-1" {...props}></Icon>
