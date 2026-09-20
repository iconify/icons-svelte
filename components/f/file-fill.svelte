<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxkgnvbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxkgnvbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-fill" {...props}></Icon>
