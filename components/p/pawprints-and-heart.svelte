<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0v7beb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s0v7beb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pawprints-and-heart" {...props}></Icon>
