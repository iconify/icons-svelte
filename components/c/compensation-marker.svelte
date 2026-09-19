<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf97cqb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="pf97cqb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:compensation-marker" {...props}></Icon>
