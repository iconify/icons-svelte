<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtqxdlbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="dtqxdlbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:readernaut" {...props}></Icon>
