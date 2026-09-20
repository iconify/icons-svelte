<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf72x4bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zf72x4bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:camera-square-remix" {...props}></Icon>
