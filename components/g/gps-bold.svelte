<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj6io99fw.css';
import '../../css/x/xrub8bc1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tj6io99fw"/><path class="xrub8bc1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gps-bold" {...props}></Icon>
