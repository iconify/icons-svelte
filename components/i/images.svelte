<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5ykg8liz.css';
import '../../css/d/dcqkl1zes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c5ykg8liz"/><path class="dcqkl1zes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:images" {...props}></Icon>
