<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_kxo3vjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g_kxo3vjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:connection" {...props}></Icon>
