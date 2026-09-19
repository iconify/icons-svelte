<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow7i0tzjj.css';
import '../../css/s/s47q5obuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow7i0tzjj"/><path class="s47q5obuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:basket" {...props}></Icon>
