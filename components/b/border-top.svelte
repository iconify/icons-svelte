<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guhg6-y-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="guhg6-y-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:border-top" {...props}></Icon>
