<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c74bkebhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1536};
const content = `<path class="c74bkebhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cc-mastercard" {...props}></Icon>
