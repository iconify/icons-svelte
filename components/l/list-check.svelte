<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvytzjb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pvytzjb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:list-check" {...props}></Icon>
