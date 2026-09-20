<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkl_yjbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gkl_yjbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:airsonic" {...props}></Icon>
