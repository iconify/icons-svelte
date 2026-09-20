<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf7yw4f_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf7yw4f_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:basketball-fill" {...props}></Icon>
