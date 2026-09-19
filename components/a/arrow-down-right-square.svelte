<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1r0tnbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d1r0tnbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-down-right-square" {...props}></Icon>
