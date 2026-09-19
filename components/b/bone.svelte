<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2_3_ztmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="w2_3_ztmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:bone" {...props}></Icon>
