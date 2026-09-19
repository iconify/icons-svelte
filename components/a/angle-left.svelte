<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-hm_y_jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="h-hm_y_jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:angle-left" {...props}></Icon>
