<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azk57blhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azk57blhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bluetooth-off-fill" {...props}></Icon>
