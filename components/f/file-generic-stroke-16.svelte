<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5xjktb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u5xjktb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-generic-stroke-16" {...props}></Icon>
