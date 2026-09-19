<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmq9nyx2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cmq9nyx2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:chart-bar" {...props}></Icon>
