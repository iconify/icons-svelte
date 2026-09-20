<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fups5pbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fups5pbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:i-in-circle" {...props}></Icon>
