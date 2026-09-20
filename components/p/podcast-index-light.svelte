<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa6e78afl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fa6e78afl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:podcast-index-light" {...props}></Icon>
