<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpx_oobfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpx_oobfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:connector-line" {...props}></Icon>
