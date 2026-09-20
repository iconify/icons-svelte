<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz1d529op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uz1d529op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:network" {...props}></Icon>
