<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcp-m_d0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jcp-m_d0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-signal" {...props}></Icon>
