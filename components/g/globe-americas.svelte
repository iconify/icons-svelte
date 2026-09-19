<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd8v6pb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rd8v6pb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:globe-americas" {...props}></Icon>
