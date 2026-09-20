<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aevgpv02h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aevgpv02h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openemr" {...props}></Icon>
