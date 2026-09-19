<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd5hjkb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="rd5hjkb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:check-square" {...props}></Icon>
