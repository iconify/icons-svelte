<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rptdwfb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rptdwfb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:book" {...props}></Icon>
