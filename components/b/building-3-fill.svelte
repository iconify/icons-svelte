<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw9awtb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dw9awtb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-3-fill" {...props}></Icon>
