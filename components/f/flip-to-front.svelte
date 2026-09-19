<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpcv03ats.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="qpcv03ats"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flip-to-front" {...props}></Icon>
