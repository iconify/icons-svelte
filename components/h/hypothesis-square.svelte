<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttu_k9btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ttu_k9btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:hypothesis-square" {...props}></Icon>
