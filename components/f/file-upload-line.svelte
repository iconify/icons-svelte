<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy0zzymhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy0zzymhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-upload-line" {...props}></Icon>
