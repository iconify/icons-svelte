<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etqrn7b3n.css';
import '../../css/y/yq_d2zbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="etqrn7b3n"/><path class="yq_d2zbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:floor-plan-20-bold" {...props}></Icon>
