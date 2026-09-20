<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri_v651ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ri_v651ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bewcloud-dark" {...props}></Icon>
