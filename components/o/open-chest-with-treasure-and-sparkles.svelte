<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y17aut7vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y17aut7vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-chest-with-treasure-and-sparkles" {...props}></Icon>
