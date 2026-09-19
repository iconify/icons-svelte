<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_2tcx1ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="v_2tcx1ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:money-bills" {...props}></Icon>
