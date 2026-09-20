<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmvtl5bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmvtl5bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-download-line" {...props}></Icon>
