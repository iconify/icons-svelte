<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_mr8vw2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_mr8vw2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pricetag-sharp" {...props}></Icon>
