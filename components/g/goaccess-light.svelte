<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuy7nabtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zuy7nabtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:goaccess-light" {...props}></Icon>
