<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa4qcbbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qa4qcbbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:flashlight" {...props}></Icon>
