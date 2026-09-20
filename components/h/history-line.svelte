<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu0p66rmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lu0p66rmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:history-line" {...props}></Icon>
