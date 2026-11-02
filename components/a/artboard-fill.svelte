<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzjz7ybat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzjz7ybat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:artboard-fill" {...props}></Icon>
