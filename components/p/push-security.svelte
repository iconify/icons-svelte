<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3wb3mu3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d3wb3mu3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:push-security" {...props}></Icon>
