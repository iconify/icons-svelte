<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-vnx3bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k-vnx3bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:adjustments-horizontal-16-solid" {...props}></Icon>
