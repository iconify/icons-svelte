<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxbe-jsqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lxbe-jsqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:i" {...props}></Icon>
