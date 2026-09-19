<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn39bsb7i.css';
import '../../css/a/aevd0o1gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn39bsb7i"/><path class="aevd0o1gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-bubble-x" {...props}></Icon>
