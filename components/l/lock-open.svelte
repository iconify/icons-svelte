<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-2gwjbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w-2gwjbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:lock-open" {...props}></Icon>
