<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf8eb6b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wf8eb6b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ark" {...props}></Icon>
