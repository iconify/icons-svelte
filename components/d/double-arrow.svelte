<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5-1y4y0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":312,"height":496};
const content = `<path class="n5-1y4y0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:double-arrow" {...props}></Icon>
