<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6qxpw2du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y6qxpw2du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:chevron-down" {...props}></Icon>
