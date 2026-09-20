<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6nlq522g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r6nlq522g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:plus-square-o" {...props}></Icon>
