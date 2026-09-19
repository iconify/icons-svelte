<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw1ho0t9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fw1ho0t9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bpmn-escalation-fill" {...props}></Icon>
