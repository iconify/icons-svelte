<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f88db6bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f88db6bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:authman-dark" {...props}></Icon>
