<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcqspba_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="mcqspba_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:reorder" {...props}></Icon>
