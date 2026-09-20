<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn7unvyzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="nn7unvyzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:candy" {...props}></Icon>
