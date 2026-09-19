<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwx53kb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vwx53kb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-cancel" {...props}></Icon>
