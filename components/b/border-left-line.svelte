<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zklsdxb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zklsdxb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-left-line" {...props}></Icon>
