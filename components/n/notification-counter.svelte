<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crncvzb-e.css';
import '../../css/t/tn0_q5b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="crncvzb-e"/><circle class="tn0_q5b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:notification-counter" {...props}></Icon>
