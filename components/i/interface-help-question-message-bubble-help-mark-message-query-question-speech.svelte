<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruhmssb4g.css';
import '../../css/f/f9g6pqpws.css';
import '../../css/s/sdn94xi5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ruhmssb4g"/><path class="f9g6pqpws"/><path class="sdn94xi5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-help-question-message-bubble-help-mark-message-query-question-speech" {...props}></Icon>
