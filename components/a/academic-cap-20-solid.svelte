<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n03cc7bmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="n03cc7bmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:academic-cap-20-solid" {...props}></Icon>
