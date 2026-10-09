<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/the3ypbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="the3ypbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:iceberg-20-bold" {...props}></Icon>
