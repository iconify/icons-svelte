<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic_j8siyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ic_j8siyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:basket-arrow-up" {...props}></Icon>
