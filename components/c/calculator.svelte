<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncsdce20j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ncsdce20j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:calculator" {...props}></Icon>
