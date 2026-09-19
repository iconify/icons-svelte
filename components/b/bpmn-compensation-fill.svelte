<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_n99qbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x_n99qbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bpmn-compensation-fill" {...props}></Icon>
