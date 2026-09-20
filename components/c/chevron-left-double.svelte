<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxbezbb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="lxbezbb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:chevron-left-double" {...props}></Icon>
