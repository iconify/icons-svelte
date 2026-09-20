<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3qt8sbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r3qt8sbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:owntracks-light" {...props}></Icon>
