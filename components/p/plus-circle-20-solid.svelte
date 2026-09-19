<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xldtzwb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xldtzwb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:plus-circle-20-solid" {...props}></Icon>
