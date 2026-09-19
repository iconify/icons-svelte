<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9n7qsxsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x9n7qsxsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:link-remove-stroke-16" {...props}></Icon>
