<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgoqdb0qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kgoqdb0qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-webcam" {...props}></Icon>
