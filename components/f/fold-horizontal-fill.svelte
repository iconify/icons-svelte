<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxl11ypsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxl11ypsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fold-horizontal-fill" {...props}></Icon>
