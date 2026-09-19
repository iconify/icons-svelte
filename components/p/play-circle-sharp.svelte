<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axuv2sb-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="axuv2sb-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:play-circle-sharp" {...props}></Icon>
