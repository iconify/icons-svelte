<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erv-4vbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="erv-4vbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:palette" {...props}></Icon>
