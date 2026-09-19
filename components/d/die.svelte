<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we_rnnwsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="we_rnnwsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:die" {...props}></Icon>
