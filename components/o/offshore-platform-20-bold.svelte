<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1d2hbbbl.css';
import '../../css/t/to__--22z.css';
import '../../css/l/lzwt4-b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t1d2hbbbl"/><path class="to__--22z"/><path class="lzwt4-b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offshore-platform-20-bold" {...props}></Icon>
