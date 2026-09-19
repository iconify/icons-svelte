<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/squd2zbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="squd2zbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:cloud-arrow-up" {...props}></Icon>
