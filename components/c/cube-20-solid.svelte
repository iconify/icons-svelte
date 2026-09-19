<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe45mab1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oe45mab1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cube-20-solid" {...props}></Icon>
