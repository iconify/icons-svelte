<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqdqp0n7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":224,"height":384};
const content = `<path class="gqdqp0n7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:money" {...props}></Icon>
