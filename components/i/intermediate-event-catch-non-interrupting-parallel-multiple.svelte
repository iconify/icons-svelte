<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zafw3kuon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zafw3kuon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-non-interrupting-parallel-multiple" {...props}></Icon>
