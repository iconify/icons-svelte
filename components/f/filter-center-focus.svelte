<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdy04lnro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="sdy04lnro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:filter-center-focus" {...props}></Icon>
