<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1hbegbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="q1hbegbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:pet-14" {...props}></Icon>
