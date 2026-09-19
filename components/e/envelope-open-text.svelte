<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvz32_b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rvz32_b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:envelope-open-text" {...props}></Icon>
