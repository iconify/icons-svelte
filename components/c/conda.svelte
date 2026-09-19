<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csta3d-ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":445,"height":512};
const content = `<path class="csta3d-ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:conda" {...props}></Icon>
