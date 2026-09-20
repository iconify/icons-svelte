<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm4iy4btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm4iy4btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-crack-line" {...props}></Icon>
