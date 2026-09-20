<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epf5evbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="epf5evbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:nature-moon" {...props}></Icon>
