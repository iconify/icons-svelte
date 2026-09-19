<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flln8sb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="flln8sb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:exclamation-lg" {...props}></Icon>
