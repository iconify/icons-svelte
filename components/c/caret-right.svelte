<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tytlidciu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tytlidciu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:caret-right" {...props}></Icon>
