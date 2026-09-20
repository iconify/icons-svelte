<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr0ize7uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hr0ize7uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chess-rook" {...props}></Icon>
