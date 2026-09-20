<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qap8vxm-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qap8vxm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mikopbx-light" {...props}></Icon>
