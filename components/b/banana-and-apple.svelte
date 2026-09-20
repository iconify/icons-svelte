<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht-nwvn7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ht-nwvn7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:banana-and-apple" {...props}></Icon>
