<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue_x4m1-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="ue_x4m1-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:chevron-up-double" {...props}></Icon>
