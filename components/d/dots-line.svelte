<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mstdqfbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mstdqfbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dots-line" {...props}></Icon>
