<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd0h02asm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd0h02asm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bath-line" {...props}></Icon>
