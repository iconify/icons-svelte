<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcw82nfcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wcw82nfcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:comment-dots" {...props}></Icon>
