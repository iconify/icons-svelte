<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvmqycc5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uvmqycc5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:photo-camera-add" {...props}></Icon>
