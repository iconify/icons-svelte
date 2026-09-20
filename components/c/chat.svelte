<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk5rwobla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tk5rwobla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:chat" {...props}></Icon>
