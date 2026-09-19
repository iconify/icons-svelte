<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_pfwqd_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_pfwqd_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:arrow-back-circle-sharp" {...props}></Icon>
