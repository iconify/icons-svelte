<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an5sm2bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="an5sm2bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:move-cross-over" {...props}></Icon>
