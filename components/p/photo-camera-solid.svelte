<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb4lhrbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yb4lhrbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:photo-camera-solid" {...props}></Icon>
