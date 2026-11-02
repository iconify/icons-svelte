<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x04u6rb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x04u6rb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-fill" {...props}></Icon>
