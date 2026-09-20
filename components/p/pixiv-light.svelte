<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veh--ghsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="veh--ghsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pixiv-light" {...props}></Icon>
