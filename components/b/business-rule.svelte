<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfwtfdz8c.css';
import '../../css/r/rzh_o5duh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="bfwtfdz8c"/><path class="rzh_o5duh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:business-rule" {...props}></Icon>
