<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_8qcixqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k_8qcixqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chart-diagram-add" {...props}></Icon>
