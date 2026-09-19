<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ack00vbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ack00vbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:arrow-down-left" {...props}></Icon>
