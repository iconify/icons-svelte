<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxijd8b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxijd8b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:play-circle-line" {...props}></Icon>
