<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie8p9lh6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ie8p9lh6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:photo-camera-cancelled" {...props}></Icon>
