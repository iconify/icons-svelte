<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsmnwl62l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsmnwl62l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bridge-2-line" {...props}></Icon>
