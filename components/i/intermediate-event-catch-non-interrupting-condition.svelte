<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi-m8xbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oi-m8xbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-catch-non-interrupting-condition" {...props}></Icon>
