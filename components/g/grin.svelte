<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp2f8t22k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="rp2f8t22k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:grin" {...props}></Icon>
