<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1wu8bb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="j1wu8bb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-upward" {...props}></Icon>
