<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_-g7nb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l_-g7nb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:caret-down" {...props}></Icon>
