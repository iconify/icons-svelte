<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1iipw_zi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="r1iipw_zi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:memory" {...props}></Icon>
