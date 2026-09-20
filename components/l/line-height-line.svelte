<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b66489byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b66489byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:line-height-line" {...props}></Icon>
