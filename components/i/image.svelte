<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7o_u2bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":439,"height":512};
const content = `<path class="k7o_u2bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:image" {...props}></Icon>
