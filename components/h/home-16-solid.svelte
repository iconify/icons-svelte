<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvwor_b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fvwor_b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:home-16-solid" {...props}></Icon>
