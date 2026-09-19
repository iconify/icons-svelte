<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8x_xccwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="a8x_xccwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calendar-20-solid" {...props}></Icon>
