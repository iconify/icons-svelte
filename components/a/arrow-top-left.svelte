<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct-4h76ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="ct-4h76ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:arrow-top-left" {...props}></Icon>
