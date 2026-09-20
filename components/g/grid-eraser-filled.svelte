<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tya28ccex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tya28ccex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid-eraser-filled" {...props}></Icon>
