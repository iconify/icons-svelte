<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbu9pnvty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbu9pnvty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ad-circle-off-line" {...props}></Icon>
