<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_mc4ya_v.css';
import '../../css/z/z56-4sbhg.css';
import '../../css/j/juse7d_jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a x_mc4ya_v"/><path class="wm-k z56-4sbhg"/><path class="juse7d_jr wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:microphone" {...props}></Icon>
