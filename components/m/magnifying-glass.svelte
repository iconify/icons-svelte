<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rar3t3bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rar3t3bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:magnifying-glass" {...props}></Icon>
