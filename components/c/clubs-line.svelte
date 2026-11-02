<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc1x0_-rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc1x0_-rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clubs-line" {...props}></Icon>
