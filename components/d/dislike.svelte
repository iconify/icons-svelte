<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n37jz3b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="n37jz3b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:dislike" {...props}></Icon>
