<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxdxw7bsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dxdxw7bsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:book-cover" {...props}></Icon>
