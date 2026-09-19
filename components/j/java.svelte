<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvp8sf1-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="jvp8sf1-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:java" {...props}></Icon>
