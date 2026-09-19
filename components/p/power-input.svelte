<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbnn0jbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="lbnn0jbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:power-input" {...props}></Icon>
