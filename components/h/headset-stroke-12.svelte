<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3_qp57di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a3_qp57di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:headset-stroke-12" {...props}></Icon>
