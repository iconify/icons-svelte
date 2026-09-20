<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkfx91bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qkfx91bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fiberstore-dark" {...props}></Icon>
