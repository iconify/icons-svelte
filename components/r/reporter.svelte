<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek2c01bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ek2c01bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:reporter" {...props}></Icon>
