<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-0pfv32i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k-0pfv32i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bookmark-16-solid" {...props}></Icon>
