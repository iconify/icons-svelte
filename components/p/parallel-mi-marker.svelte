<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw70umb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="hw70umb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:parallel-mi-marker" {...props}></Icon>
