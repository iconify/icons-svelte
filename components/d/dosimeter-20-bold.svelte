<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b63t5_b0n.css';
import '../../css/u/ufacyhbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b63t5_b0n"/><path class="ufacyhbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dosimeter-20-bold" {...props}></Icon>
