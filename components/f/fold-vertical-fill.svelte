<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdhb_e1dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdhb_e1dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fold-vertical-fill" {...props}></Icon>
