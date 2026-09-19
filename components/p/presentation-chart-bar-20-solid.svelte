<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-b4ufqaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d-b4ufqaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:presentation-chart-bar-20-solid" {...props}></Icon>
