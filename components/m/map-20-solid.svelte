<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t084e5b0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="t084e5b0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:map-20-solid" {...props}></Icon>
