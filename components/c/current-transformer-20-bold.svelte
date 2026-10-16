<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o04_3t6ej.css';
import '../../css/k/ktlm5_bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o04_3t6ej"/><path class="ktlm5_bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:current-transformer-20-bold" {...props}></Icon>
