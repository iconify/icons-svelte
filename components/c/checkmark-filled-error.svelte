<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c55vgcbjc.css';
import '../../css/h/h7v4f1b-l.css';
import '../../css/c/cyoweacxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c55vgcbjc"/><path class="h7v4f1b-l"/><path class="cyoweacxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:checkmark-filled-error" {...props}></Icon>
