<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eiixxumxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="eiixxumxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:h-3" {...props}></Icon>
