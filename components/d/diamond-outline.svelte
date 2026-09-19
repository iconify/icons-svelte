<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdf6hiznz.css';
import '../../css/v/vnfkbkbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zdf6hiznz"/><path class="vnfkbkbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:diamond-outline" {...props}></Icon>
