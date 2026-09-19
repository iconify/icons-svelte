<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6k-pbc_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="b6k-pbc_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hands-holding-circle" {...props}></Icon>
