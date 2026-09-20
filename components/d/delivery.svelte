<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpl65cc6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rpl65cc6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:delivery" {...props}></Icon>
