<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fygf62kln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fygf62kln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:record-vinyl" {...props}></Icon>
