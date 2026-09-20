<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivrd68bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ivrd68bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:controls-horizontal" {...props}></Icon>
