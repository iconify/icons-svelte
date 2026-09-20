<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vykxr_z_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vykxr_z_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jinear-light" {...props}></Icon>
