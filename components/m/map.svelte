<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff375zpxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ff375zpxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:map" {...props}></Icon>
