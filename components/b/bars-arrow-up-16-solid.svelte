<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ps3ce9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p7ps3ce9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bars-arrow-up-16-solid" {...props}></Icon>
