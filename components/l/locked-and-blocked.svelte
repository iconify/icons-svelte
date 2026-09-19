<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvzxvjb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vvzxvjb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:locked-and-blocked" {...props}></Icon>
