<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxc6vr24n.css';
import '../../css/l/lc94xtz6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="mxc6vr24n"/><path class="lc94xtz6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-camera-home" {...props}></Icon>
