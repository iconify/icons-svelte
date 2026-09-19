<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkw82pbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wkw82pbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:male-female" {...props}></Icon>
