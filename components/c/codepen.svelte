<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me7di4b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="me7di4b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:codepen" {...props}></Icon>
