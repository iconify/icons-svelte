<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtymrw8dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rtymrw8dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:noton-dark" {...props}></Icon>
