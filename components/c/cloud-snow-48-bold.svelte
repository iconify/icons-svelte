<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-trq2_bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k-trq2_bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-snow-48-bold" {...props}></Icon>
