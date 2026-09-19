<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot1lbzb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ot1lbzb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:acmdl" {...props}></Icon>
