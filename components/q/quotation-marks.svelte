<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-ce26b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x-ce26b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:quotation-marks" {...props}></Icon>
