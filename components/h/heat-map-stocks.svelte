<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6xhyebnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e6xhyebnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:heat-map-stocks" {...props}></Icon>
