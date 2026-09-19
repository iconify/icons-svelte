<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhv6hlbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xhv6hlbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:folder-plus-20-solid" {...props}></Icon>
