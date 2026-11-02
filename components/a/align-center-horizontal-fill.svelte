<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzzo-_u8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzzo-_u8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-center-horizontal-fill" {...props}></Icon>
