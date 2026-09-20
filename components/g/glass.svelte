<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lok1r60yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lok1r60yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:glass" {...props}></Icon>
