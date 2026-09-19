<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn9b5bcba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":328,"height":512};
const content = `<path class="vn9b5bcba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:girl-user" {...props}></Icon>
