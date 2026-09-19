<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-2gqjb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j-2gqjb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:binoculars" {...props}></Icon>
