<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvtqc-bnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rvtqc-bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:media-step-forward" {...props}></Icon>
