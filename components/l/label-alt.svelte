<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfq-i7j7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="vfq-i7j7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:label-alt" {...props}></Icon>
