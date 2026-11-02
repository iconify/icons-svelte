<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky9_qybkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky9_qybkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fishing-hook-line" {...props}></Icon>
