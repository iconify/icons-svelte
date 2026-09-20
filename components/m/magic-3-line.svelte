<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uon7ubcpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uon7ubcpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magic-3-line" {...props}></Icon>
