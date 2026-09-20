<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hec03xb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hec03xb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hands-clapping-line" {...props}></Icon>
