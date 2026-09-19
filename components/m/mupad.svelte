<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp_hivq3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":494,"height":512};
const content = `<path class="zp_hivq3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:mupad" {...props}></Icon>
