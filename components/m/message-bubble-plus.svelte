<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2y2tbcyw.css';
import '../../css/a/aevd0o1gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2y2tbcyw"/><path class="aevd0o1gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-plus" {...props}></Icon>
