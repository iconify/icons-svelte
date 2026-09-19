<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztfbiebtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ztfbiebtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:attach-sharp" {...props}></Icon>
