<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmiwrrb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lmiwrrb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hot-tub-person" {...props}></Icon>
