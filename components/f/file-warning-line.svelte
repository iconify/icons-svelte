<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_cbpvx_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_cbpvx_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-warning-line" {...props}></Icon>
