<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzi-y4bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tzi-y4bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:global" {...props}></Icon>
