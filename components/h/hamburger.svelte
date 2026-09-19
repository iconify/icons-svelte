<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7q-v7b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="v7q-v7b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:hamburger" {...props}></Icon>
