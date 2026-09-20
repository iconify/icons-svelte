<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwz5anb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vwz5anb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:resolving" {...props}></Icon>
