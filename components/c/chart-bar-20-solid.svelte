<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypzybbb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ypzybbb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chart-bar-20-solid" {...props}></Icon>
