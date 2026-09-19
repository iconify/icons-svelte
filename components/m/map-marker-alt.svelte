<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7t5znbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="n7t5znbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:map-marker-alt" {...props}></Icon>
