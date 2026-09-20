<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd-is8u-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rd-is8u-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:funnel" {...props}></Icon>
