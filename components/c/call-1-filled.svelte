<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy3525bwm.css';
import '../../css/d/d7q3yfbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wy3525bwm"/><path class="d7q3yfbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:call-1-filled" {...props}></Icon>
