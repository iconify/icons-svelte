<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_9-f9blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_9-f9blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:download-2-fill" {...props}></Icon>
