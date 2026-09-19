<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxrevhb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uxrevhb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-left-fill-16" {...props}></Icon>
