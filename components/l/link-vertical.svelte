<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re9pfrb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="re9pfrb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:link-vertical" {...props}></Icon>
