<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8nrbqb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x8nrbqb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:browser-safari" {...props}></Icon>
