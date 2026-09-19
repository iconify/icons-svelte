<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efp6-abvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="efp6-abvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mouse-pointer" {...props}></Icon>
