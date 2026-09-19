<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkgktuauf.css';
import '../../css/k/k-vylvb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dkgktuauf"/><path class="k-vylvb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:right-up2" {...props}></Icon>
