<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlb2ztnyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rlb2ztnyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:dial-pad-finger-2" {...props}></Icon>
