<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjqcbzv4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="bjqcbzv4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:l" {...props}></Icon>
