<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc0hhlbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1536};
const content = `<path class="qc0hhlbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bookmark-o" {...props}></Icon>
