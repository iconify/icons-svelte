<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clrdxwbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clrdxwbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cactus-line" {...props}></Icon>
