<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_ka6f25f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r_ka6f25f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:border-top" {...props}></Icon>
