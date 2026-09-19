<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z67c-1big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z67c-1big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:phone" {...props}></Icon>
