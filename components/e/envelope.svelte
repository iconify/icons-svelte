<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm3g_gb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dm3g_gb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:envelope" {...props}></Icon>
