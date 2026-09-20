<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve2a2gbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ve2a2gbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:move" {...props}></Icon>
