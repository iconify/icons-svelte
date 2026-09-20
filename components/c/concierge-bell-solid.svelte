<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdtdpfb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jdtdpfb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:concierge-bell-solid" {...props}></Icon>
