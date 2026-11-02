<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccx1e7b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccx1e7b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:oil-line" {...props}></Icon>
