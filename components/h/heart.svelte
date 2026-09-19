<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppw-j8-ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ppw-j8-ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:heart" {...props}></Icon>
