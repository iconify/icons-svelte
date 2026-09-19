<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j43vdgeku.css';
import '../../css/a/aevd0o1gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j43vdgeku"/><path class="aevd0o1gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-detail" {...props}></Icon>
