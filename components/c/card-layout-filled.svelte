<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co6w5rbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="co6w5rbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:card-layout-filled" {...props}></Icon>
