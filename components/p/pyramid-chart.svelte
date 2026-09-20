<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0f47ac3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k0f47ac3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:pyramid-chart" {...props}></Icon>
