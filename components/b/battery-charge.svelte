<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk9loab2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":456};
const content = `<path class="pk9loab2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:battery-charge" {...props}></Icon>
