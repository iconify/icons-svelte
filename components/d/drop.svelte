<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyent6gbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="fyent6gbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:drop" {...props}></Icon>
