<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a70ga4nnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a70ga4nnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:glass-whiskey" {...props}></Icon>
