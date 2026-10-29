<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utqzt6bcp.css';
import '../../css/q/qt8u0z4vf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utqzt6bcp wm-k"/><path class="qt8u0z4vf wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:frown" {...props}></Icon>
