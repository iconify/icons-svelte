<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vom63sb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vom63sb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:horse-in-shelter" {...props}></Icon>
