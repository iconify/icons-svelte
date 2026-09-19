<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr-donbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="jr-donbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:hand-tool" {...props}></Icon>
