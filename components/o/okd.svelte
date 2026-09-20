<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu_x1-bzu.css';
import '../../css/y/ys_vvx_-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iu_x1-bzu"/><path class="ys_vvx_-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:okd" {...props}></Icon>
