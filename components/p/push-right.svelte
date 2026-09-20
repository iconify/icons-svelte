<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux__kacnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="ux__kacnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:push-right" {...props}></Icon>
