<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0xvj0b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v0xvj0b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:contact-book" {...props}></Icon>
