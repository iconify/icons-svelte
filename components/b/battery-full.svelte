<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0k5xydhj.css';
import '../../css/h/h0r0o6bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n0k5xydhj"/><path class="h0r0o6bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:battery-full" {...props}></Icon>
