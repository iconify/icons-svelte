<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf9uo9box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="wf9uo9box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:plug-solid" {...props}></Icon>
