<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-3y3_nir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-3y3_nir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-scan-line" {...props}></Icon>
