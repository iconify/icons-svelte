<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg9unybms.css';
import '../../css/f/fv0y09b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vg9unybms"/><path class="fv0y09b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chili3d" {...props}></Icon>
