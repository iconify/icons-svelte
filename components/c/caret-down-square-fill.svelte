<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3nac-40h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z3nac-40h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:caret-down-square-fill" {...props}></Icon>
