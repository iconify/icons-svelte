<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9ghevbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="d9ghevbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:forcus" {...props}></Icon>
