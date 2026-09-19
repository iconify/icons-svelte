<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/famtd3kbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="famtd3kbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bookmark-20-solid" {...props}></Icon>
