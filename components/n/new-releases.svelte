<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb_gupbgs.css';
import '../../css/i/iquxmufry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jb_gupbgs"/><path class="iquxmufry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:new-releases" {...props}></Icon>
