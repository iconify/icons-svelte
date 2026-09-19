<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivpjwx_1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ivpjwx_1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:mail-empty" {...props}></Icon>
