<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqu1uhb_e.css';
import '../../css/b/b0zme1q_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqu1uhb_e"/><path class="b0zme1q_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:controls-camera-off" {...props}></Icon>
