<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rypl5_97b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rypl5_97b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hpe-aruba" {...props}></Icon>
