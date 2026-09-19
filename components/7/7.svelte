<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n520rw5zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="n520rw5zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:7" {...props}></Icon>
