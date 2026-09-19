<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvycimbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rvycimbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:building-storefront-20-solid" {...props}></Icon>
