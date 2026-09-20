<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4i712_no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e4i712_no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:orthodox" {...props}></Icon>
