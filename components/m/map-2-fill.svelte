<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9kii2bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9kii2bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-2-fill" {...props}></Icon>
