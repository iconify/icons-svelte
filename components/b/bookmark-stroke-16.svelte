<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf95xxbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lf95xxbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bookmark-stroke-16" {...props}></Icon>
