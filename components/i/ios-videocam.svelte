<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drmjsqkyz.css';
import '../../css/r/rab5k-b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="drmjsqkyz"/><path class="rab5k-b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-videocam" {...props}></Icon>
