<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw5xzmb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw5xzmb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrows-right-fill" {...props}></Icon>
