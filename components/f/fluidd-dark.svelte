<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh3nr0brd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bh3nr0brd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fluidd-dark" {...props}></Icon>
