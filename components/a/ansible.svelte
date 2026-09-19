<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh8u1bb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nh8u1bb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ansible" {...props}></Icon>
