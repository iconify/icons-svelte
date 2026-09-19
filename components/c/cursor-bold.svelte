<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1aasd4zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1aasd4zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cursor-bold" {...props}></Icon>
