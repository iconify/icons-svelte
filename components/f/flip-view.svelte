<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqqfo_bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="zqqfo_bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:flip-view" {...props}></Icon>
