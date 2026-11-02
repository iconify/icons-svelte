<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrcs06bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrcs06bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:low-temperature-line" {...props}></Icon>
