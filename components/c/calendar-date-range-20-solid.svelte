<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj-krkb_k.css';
import '../../css/a/a8x_xccwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cj-krkb_k"/><path clip-rule="evenodd" class="a8x_xccwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calendar-date-range-20-solid" {...props}></Icon>
