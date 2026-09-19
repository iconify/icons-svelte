<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgci88bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bgci88bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-90deg-down" {...props}></Icon>
