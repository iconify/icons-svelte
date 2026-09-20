<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f63fvf6ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f63fvf6ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:disconnected" {...props}></Icon>
