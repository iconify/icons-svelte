<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/proji4grm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="proji4grm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cruzeiro-sign" {...props}></Icon>
