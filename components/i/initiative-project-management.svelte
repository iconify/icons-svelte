<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u01w8rbik.css';
import '../../css/m/m5ihdsbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u01w8rbik"/><path class="m5ihdsbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:initiative-project-management" {...props}></Icon>
