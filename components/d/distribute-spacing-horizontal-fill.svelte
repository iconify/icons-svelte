<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0in5lbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0in5lbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:distribute-spacing-horizontal-fill" {...props}></Icon>
