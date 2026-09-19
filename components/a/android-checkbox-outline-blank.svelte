<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xngyb4r-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xngyb4r-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-checkbox-outline-blank" {...props}></Icon>
