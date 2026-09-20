<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9t93yomg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d9t93yomg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:left-square-o" {...props}></Icon>
