<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnzwy0uxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bnzwy0uxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opencloud" {...props}></Icon>
