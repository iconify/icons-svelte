<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0e2_bc4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="f0e2_bc4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:church" {...props}></Icon>
