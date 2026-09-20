<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6ptxrgvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l6ptxrgvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:equalizer-1" {...props}></Icon>
