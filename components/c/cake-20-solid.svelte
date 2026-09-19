<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6l8k0bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g6l8k0bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cake-20-solid" {...props}></Icon>
