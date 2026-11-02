<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2k63wbaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2k63wbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-bar-big-line" {...props}></Icon>
