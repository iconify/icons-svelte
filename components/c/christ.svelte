<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stjril7pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="stjril7pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:christ" {...props}></Icon>
