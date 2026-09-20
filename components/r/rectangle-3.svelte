<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3i8h8b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p3i8h8b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:rectangle-3" {...props}></Icon>
