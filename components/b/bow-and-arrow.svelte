<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_4hj9vhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u_4hj9vhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:bow-and-arrow" {...props}></Icon>
