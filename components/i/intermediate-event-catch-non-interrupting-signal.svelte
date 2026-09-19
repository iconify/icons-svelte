<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klu-8qj5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="klu-8qj5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-non-interrupting-signal" {...props}></Icon>
