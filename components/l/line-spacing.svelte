<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w99iq9bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w99iq9bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:line-spacing" {...props}></Icon>
