<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-8ikw0ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s-8ikw0ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bpmn-error-outline" {...props}></Icon>
