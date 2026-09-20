<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eekg15-bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eekg15-bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fandom-light" {...props}></Icon>
