<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0aye_mhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b0aye_mhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chili3d-light" {...props}></Icon>
