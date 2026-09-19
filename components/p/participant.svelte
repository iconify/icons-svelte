<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9z1xfbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="w9z1xfbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:participant" {...props}></Icon>
