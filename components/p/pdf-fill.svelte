<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz55eabvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz55eabvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pdf-fill" {...props}></Icon>
