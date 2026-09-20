<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3wbsm0fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z3wbsm0fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-table" {...props}></Icon>
