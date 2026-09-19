<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp180xbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xp180xbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:flash-outline" {...props}></Icon>
