<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmk60pbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmk60pbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:forward-fill" {...props}></Icon>
