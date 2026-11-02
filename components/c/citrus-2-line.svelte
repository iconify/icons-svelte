<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tefh-wl-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tefh-wl-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:citrus-2-line" {...props}></Icon>
