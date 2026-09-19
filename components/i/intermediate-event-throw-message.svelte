<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqa4lnbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="lqa4lnbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:intermediate-event-throw-message" {...props}></Icon>
