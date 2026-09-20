<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qodm7xjge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qodm7xjge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:photo-camera-filled" {...props}></Icon>
