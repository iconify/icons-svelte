<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp0257bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="mp0257bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:book-open" {...props}></Icon>
