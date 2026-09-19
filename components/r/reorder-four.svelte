<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiqbcvbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uiqbcvbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:reorder-four" {...props}></Icon>
