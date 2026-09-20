<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex_e1-b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ex_e1-b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-right-chevron" {...props}></Icon>
