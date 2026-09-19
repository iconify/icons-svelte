<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq25edcdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="eq25edcdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:r-bold" {...props}></Icon>
