<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td4grnbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="td4grnbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:hand-point-right" {...props}></Icon>
