<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdwazzbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vdwazzbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:open-panel-filled-bottom" {...props}></Icon>
