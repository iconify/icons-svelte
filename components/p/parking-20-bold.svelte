<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we2agujqc.css';
import '../../css/e/eie_cccui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="we2agujqc"/><path class="eie_cccui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:parking-20-bold" {...props}></Icon>
