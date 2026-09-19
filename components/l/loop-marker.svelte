<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fajg1w5pf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="fajg1w5pf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:loop-marker" {...props}></Icon>
