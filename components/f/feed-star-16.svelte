<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffjsxmbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ffjsxmbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-star-16" {...props}></Icon>
