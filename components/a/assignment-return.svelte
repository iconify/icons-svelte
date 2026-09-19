<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j31pc0nke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="j31pc0nke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:assignment-return" {...props}></Icon>
