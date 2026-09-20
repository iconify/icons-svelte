<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eih4zpioh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eih4zpioh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-venus-mars" {...props}></Icon>
