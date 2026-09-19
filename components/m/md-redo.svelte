<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7pga0bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z7pga0bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-redo" {...props}></Icon>
