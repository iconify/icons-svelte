<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myvz9sgsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myvz9sgsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rainbow-line" {...props}></Icon>
