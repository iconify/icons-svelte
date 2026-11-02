<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vygf5iblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vygf5iblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ebike-line" {...props}></Icon>
