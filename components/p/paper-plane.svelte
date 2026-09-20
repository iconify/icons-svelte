<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj5x9wddi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="oj5x9wddi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:paper-plane" {...props}></Icon>
