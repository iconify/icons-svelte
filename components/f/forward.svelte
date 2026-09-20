<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5-o9ybxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="f5-o9ybxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:forward" {...props}></Icon>
