<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kduu9pbdz.css';
import '../../css/n/nsxom22ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kduu9pbdz"/><path class="nsxom22ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:css3-dark" {...props}></Icon>
