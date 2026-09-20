<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y96dk-70z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="y96dk-70z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chess-king" {...props}></Icon>
