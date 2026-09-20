<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckvvnsb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ckvvnsb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-star-of-david" {...props}></Icon>
