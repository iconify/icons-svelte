<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_lpopb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_lpopb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:gams" {...props}></Icon>
