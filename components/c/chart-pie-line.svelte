<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn_m2bm7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn_m2bm7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-pie-line" {...props}></Icon>
