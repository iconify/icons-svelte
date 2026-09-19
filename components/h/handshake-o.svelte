<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8je3wbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1472};
const content = `<path class="d8je3wbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:handshake-o" {...props}></Icon>
