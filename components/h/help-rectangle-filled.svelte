<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3gi7896k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3gi7896k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:help-rectangle-filled" {...props}></Icon>
