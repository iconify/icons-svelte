<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tummrfb8r.css';
import '../../css/e/esxa21aaa.css';
import '../../css/x/x0ibg6b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tummrfb8r"/><path class="esxa21aaa"/><path class="x0ibg6b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:cluster-management-outlined" {...props}></Icon>
