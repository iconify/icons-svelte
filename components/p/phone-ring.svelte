<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcoy4fbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mcoy4fbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:phone-ring" {...props}></Icon>
