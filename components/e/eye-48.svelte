<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmxr2fy_x.css';
import '../../css/j/j3eacdoxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bmxr2fy_x"/><path class="j3eacdoxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-48" {...props}></Icon>
