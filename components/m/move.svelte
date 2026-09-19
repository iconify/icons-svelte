<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_2witbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e_2witbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:move" {...props}></Icon>
