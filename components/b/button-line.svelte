<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb91dun3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb91dun3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:button-line" {...props}></Icon>
