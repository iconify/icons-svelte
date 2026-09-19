<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t91s7oy2f.css';
import '../../css/u/uti5_1b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t91s7oy2f"/><path class="uti5_1b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:bolt-circle" {...props}></Icon>
