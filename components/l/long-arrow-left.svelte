<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bys7cd0-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="bys7cd0-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:long-arrow-left" {...props}></Icon>
