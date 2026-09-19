<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx_alt8-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jx_alt8-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-non-interrupting-escalation" {...props}></Icon>
