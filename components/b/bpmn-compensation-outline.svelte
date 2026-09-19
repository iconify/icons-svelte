<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gte1i1jyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gte1i1jyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bpmn-compensation-outline" {...props}></Icon>
