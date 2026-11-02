<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plm5xnbgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plm5xnbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-axis-3d-line" {...props}></Icon>
