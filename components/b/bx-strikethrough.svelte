<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk4c0x2at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk4c0x2at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-strikethrough" {...props}></Icon>
