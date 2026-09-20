<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz9d3bbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz9d3bbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-horizontal-distribute-start-sharp" {...props}></Icon>
