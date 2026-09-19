<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6cxf3bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6cxf3bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:office-365" {...props}></Icon>
