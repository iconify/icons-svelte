<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3mkz8aiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3mkz8aiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:arrow-down-diamond" {...props}></Icon>
