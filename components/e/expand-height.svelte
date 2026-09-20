<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxahy_bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="cxahy_bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:expand-height" {...props}></Icon>
