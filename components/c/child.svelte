<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plg_1db1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="plg_1db1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:child" {...props}></Icon>
