<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4jwq-blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4jwq-blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hoe-line" {...props}></Icon>
