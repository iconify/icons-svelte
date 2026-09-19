<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4iwixnnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="p4iwixnnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person" {...props}></Icon>
