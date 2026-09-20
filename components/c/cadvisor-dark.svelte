<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj3qpibvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uj3qpibvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cadvisor-dark" {...props}></Icon>
