<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2r3y2b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2r3y2b5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hands-clapping-line" {...props}></Icon>
