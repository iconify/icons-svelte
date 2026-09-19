<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftykwmc2g.css';
import '../../css/v/vzzdp4b2g.css';
import '../../css/b/bnuokeb_v.css';
import '../../css/o/o0lqhvmmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ftykwmc2g"/><path class="vzzdp4b2g"/><path class="bnuokeb_v"/><circle class="o0lqhvmmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:man-outline" {...props}></Icon>
