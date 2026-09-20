<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8s5c1zub.css';
import '../../css/r/rlm82lo4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="t8s5c1zub"/><path class="rlm82lo4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-down-circle" {...props}></Icon>
