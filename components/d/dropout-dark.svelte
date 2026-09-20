<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v86846boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v86846boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dropout-dark" {...props}></Icon>
