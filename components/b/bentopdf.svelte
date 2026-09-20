<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bid-turbb.css';
import '../../css/t/t7741obxh.css';
import '../../css/c/cjo2vfb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bid-turbb"/><path class="t7741obxh"/><path class="cjo2vfb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bentopdf" {...props}></Icon>
