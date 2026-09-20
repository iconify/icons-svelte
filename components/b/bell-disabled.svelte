<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd6qlqben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="hd6qlqben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:bell-disabled" {...props}></Icon>
