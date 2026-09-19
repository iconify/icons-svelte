<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn-43ri1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rn-43ri1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:building-storefront-16-solid" {...props}></Icon>
