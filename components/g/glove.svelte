<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad7m-0ypo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ad7m-0ypo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:glove" {...props}></Icon>
