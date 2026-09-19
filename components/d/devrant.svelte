<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvcvb6bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qvcvb6bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:devrant" {...props}></Icon>
