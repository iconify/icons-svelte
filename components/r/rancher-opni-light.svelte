<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn8jj9htz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qn8jj9htz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-opni-light" {...props}></Icon>
