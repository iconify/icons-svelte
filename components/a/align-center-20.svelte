<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-0u-abei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h-0u-abei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-center-20" {...props}></Icon>
