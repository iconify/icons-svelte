<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycl9gobdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":329,"height":512};
const content = `<path class="ycl9gobdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:lookml" {...props}></Icon>
