<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpsrhxbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jpsrhxbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flash-off-filled" {...props}></Icon>
