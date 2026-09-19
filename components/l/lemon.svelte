<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfi9oobug.css';
import '../../css/b/b_wglmqab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jfi9oobug"/><path class="b_wglmqab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:lemon" {...props}></Icon>
