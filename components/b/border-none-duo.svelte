<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx4291bta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="hx4291bta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:border-none-duo" {...props}></Icon>
