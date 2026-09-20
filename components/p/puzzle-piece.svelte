<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmae0kb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hmae0kb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:puzzle-piece" {...props}></Icon>
