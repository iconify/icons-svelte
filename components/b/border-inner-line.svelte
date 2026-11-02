<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpwgisbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpwgisbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-inner-line" {...props}></Icon>
