<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mjzvuibua.css';
import '../../css/b/b5nir9bma.css';
import '../../css/o/oc02p8b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mjzvuibua"/><path class="b5nir9bma wm-a"/><path class="oc02p8b1x wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:peacock-feather" {...props}></Icon>
