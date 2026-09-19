<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opnm4c39e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="opnm4c39e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:patch-minus-fill" {...props}></Icon>
