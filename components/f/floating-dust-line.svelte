<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_w4j6r0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_w4j6r0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:floating-dust-line" {...props}></Icon>
