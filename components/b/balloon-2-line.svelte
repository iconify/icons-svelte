<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3x8n35ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3x8n35ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:balloon-2-line" {...props}></Icon>
