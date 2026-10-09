<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkdf61nwz.css';
import '../../css/h/hubzclpum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rkdf61nwz"/><path class="hubzclpum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:download-cloud-20" {...props}></Icon>
