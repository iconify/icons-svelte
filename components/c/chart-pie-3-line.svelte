<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sba8lluyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sba8lluyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-pie-3-line" {...props}></Icon>
