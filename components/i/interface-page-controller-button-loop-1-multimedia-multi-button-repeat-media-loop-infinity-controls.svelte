<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wba2_jwct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wba2_jwct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-page-controller-button-loop-1-multimedia-multi-button-repeat-media-loop-infinity-controls" {...props}></Icon>
