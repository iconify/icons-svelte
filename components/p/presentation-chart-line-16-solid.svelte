<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vji5wybmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vji5wybmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:presentation-chart-line-16-solid" {...props}></Icon>
