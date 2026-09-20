<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkple6bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pkple6bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:airboat" {...props}></Icon>
