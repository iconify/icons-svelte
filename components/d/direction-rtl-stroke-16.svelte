<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocasf0cop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ocasf0cop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:direction-rtl-stroke-16" {...props}></Icon>
