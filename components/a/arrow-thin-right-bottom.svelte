<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/febx_bbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="febx_bbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-thin-right-bottom" {...props}></Icon>
