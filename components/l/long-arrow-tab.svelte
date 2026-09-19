<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg8nhebwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":384};
const content = `<path class="hg8nhebwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:long-arrow-tab" {...props}></Icon>
