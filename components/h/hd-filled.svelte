<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h717r1b5y.css';
import '../../css/q/qvcljuewd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h717r1b5y"/><path class="qvcljuewd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hd-filled" {...props}></Icon>
