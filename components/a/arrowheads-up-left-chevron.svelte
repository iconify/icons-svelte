<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u00wypjwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u00wypjwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-up-left-chevron" {...props}></Icon>
