<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8ek9lc9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s8ek9lc9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:battery-empty" {...props}></Icon>
