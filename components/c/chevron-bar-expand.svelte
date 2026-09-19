<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3unwibut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w3unwibut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chevron-bar-expand" {...props}></Icon>
