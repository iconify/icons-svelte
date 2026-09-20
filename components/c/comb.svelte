<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckhx8tb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ckhx8tb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:comb" {...props}></Icon>
