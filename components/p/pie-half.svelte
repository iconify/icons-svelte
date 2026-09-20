<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjp-q-2bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="wjp-q-2bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:pie-half" {...props}></Icon>
