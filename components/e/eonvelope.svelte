<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4zh2mqii.css';
import '../../css/g/g0wt4tw1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t4zh2mqii"/><path class="g0wt4tw1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eonvelope" {...props}></Icon>
