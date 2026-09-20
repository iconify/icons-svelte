<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3vhv3bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="i3vhv3bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:funnel" {...props}></Icon>
