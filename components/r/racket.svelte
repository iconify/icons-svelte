<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv2_abjze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bv2_abjze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:racket" {...props}></Icon>
