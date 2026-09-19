<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb34d8b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="pb34d8b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:long-arrow-alt-down" {...props}></Icon>
