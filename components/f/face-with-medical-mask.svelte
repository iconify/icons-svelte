<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w254xvbma.css';
import '../../css/x/xdp90xgqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w254xvbma"/><path clip-rule="evenodd" class="xdp90xgqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:face-with-medical-mask" {...props}></Icon>
