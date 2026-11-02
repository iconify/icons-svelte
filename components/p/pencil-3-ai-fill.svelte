<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn-fuccrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn-fuccrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-3-ai-fill" {...props}></Icon>
