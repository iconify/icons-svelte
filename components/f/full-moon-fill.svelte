<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbu34-6ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbu34-6ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:full-moon-fill" {...props}></Icon>
